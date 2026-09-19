<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl4-n0bhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zl4-n0bhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:blockchain" {...props}></Icon>
