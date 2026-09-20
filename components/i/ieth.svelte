<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7hsp1bfr.css';
import '../../css/b/bn2tkibzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f7hsp1bfr"/><path class="bn2tkibzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ieth" {...props}></Icon>
