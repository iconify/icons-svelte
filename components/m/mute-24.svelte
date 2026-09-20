<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd-rm_hvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rd-rm_hvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:mute-24" {...props}></Icon>
