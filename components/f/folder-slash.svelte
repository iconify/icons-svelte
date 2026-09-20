<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3vgb6d6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3vgb6d6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:folder-slash" {...props}></Icon>
