<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogns7qblp.css';
import '../../css/v/vqarvxxid.css';
import '../../css/g/gfgm58bvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ogns7qblp"/><path class="vqarvxxid"/><path class="gfgm58bvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dashlit-light" {...props}></Icon>
