<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpmyxrb0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dpmyxrb0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-3-line" {...props}></Icon>
