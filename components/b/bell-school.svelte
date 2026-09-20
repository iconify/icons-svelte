<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/c/cm7blcben.css';
import '../../css/r/rf-v0-ybr.css';
import '../../css/z/zvulze01h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cm7blcben"/><path class="rf-v0-ybr"/><path class="zvulze01h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bell-school" {...props}></Icon>
