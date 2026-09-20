<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klxobdy9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="klxobdy9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:octoprint-light" {...props}></Icon>
