<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/g/gpnm6aciu.css';
import '../../css/m/mo9yrp11u.css';
import '../../css/v/vcqmbfvcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="gpnm6aciu"/><path class="mo9yrp11u"/><path class="vcqmbfvcz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:camera-print" {...props}></Icon>
