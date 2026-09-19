<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adkp4jfoq.css';
import '../../css/r/r0_huqbdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="adkp4jfoq"/><path class="r0_huqbdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pricing-consumption" {...props}></Icon>
