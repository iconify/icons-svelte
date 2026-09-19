<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqd8fcboz.css';
import '../../css/p/pg9erg_-c.css';
import '../../css/k/kq50e_bbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="hqd8fcboz"><circle class="pg9erg_-c"/><path class="kq50e_bbn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gala:remove" {...props}></Icon>
