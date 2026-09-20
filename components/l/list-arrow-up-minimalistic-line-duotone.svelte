<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/s19aowben.css';
import '../../css/f/f6p-2g58b.css';
import '../../css/o/o8ymreppw.css';
import '../../css/h/hjhjwb4fd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="s19aowben"/><path class="f6p-2g58b"/><path class="o8ymreppw"/><path class="hjhjwb4fd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-arrow-up-minimalistic-line-duotone" {...props}></Icon>
