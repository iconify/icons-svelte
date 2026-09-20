<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unc2embyj.css';
import '../../css/d/dr0ul_4qw.css';
import '../../css/j/jdgi2gcts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="unc2embyj"><path class="dr0ul_4qw"/><path class="jdgi2gcts"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:basket-duotone-line" {...props}></Icon>
