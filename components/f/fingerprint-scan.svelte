<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlj98nmzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlj98nmzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:fingerprint-scan" {...props}></Icon>
