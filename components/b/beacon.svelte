<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgk_kmbwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zgk_kmbwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:beacon" {...props}></Icon>
