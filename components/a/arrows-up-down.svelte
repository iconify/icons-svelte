<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycj6sccto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ycj6sccto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:arrows-up-down" {...props}></Icon>
