<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzh6_5bci.css';
import '../../css/t/t987snbfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vzh6_5bci"/><path class="t987snbfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-watson-openscale" {...props}></Icon>
