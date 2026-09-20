<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2lnfbf4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l2lnfbf4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:r-dark" {...props}></Icon>
