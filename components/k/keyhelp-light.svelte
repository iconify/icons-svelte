<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9vj76spy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w9vj76spy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:keyhelp-light" {...props}></Icon>
