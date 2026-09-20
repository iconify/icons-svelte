<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhg80cclb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vhg80cclb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:disney-plus-dark" {...props}></Icon>
