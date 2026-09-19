<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/w/w-_b78bpw.css';
import '../../css/d/dw1ryfpfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<defs><filter id="SVGhQBVIeTv" color-interpolation-filters="auto"><feColorMatrix in="SourceGraphic" values="0 0 0 0 1.000000 0 0 0 0 1.000000 0 0 0 0 1.000000 0 0 0 1.000000 0"/></filter></defs><g class="bi12bsetm"><circle class="w-_b78bpw"/><g filter="url(#SVGhQBVIeTv)"><path class="dw1ryfpfn"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:grt" {...props}></Icon>
