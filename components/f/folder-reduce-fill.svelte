<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow_z9l4da.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ow_z9l4da"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-reduce-fill" {...props}></Icon>
