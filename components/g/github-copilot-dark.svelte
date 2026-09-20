<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwuo3q2qx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pwuo3q2qx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:github-copilot-dark" {...props}></Icon>
