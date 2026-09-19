<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ups_s6b9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ups_s6b9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:dta" {...props}></Icon>
