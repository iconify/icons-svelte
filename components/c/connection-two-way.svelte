<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7-5t4bnl.css';
import '../../css/h/hgamat_lc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q7-5t4bnl"/><path class="hgamat_lc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:connection-two-way" {...props}></Icon>
