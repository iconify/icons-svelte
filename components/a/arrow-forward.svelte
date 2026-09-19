<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0e3n1ckb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="q0e3n1ckb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:arrow-forward" {...props}></Icon>
