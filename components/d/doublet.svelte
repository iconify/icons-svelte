<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5k1i-lbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q5k1i-lbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:doublet" {...props}></Icon>
