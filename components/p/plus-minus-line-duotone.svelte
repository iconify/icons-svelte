<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/jsj8gunlj.css';
import '../../css/m/mzmeouzvr.css';
import '../../css/i/ifpcpz80t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jsj8gunlj"/><path class="mzmeouzvr"/><path class="ifpcpz80t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:plus-minus-line-duotone" {...props}></Icon>
