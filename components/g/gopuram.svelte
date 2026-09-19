<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyf64obgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="kyf64obgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:gopuram" {...props}></Icon>
