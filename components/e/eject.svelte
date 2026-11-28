<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zaryj4bxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zaryj4bxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:eject" {...props}></Icon>
