<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmppwob5e.css';
import '../../css/o/o2w8gbcee.css';
import '../../css/v/vc01epbab.css';
import '../../css/n/nre--kigg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="cmppwob5e"/><path class="o2w8gbcee"/><circle class="vc01epbab"/><path class="nre--kigg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:location-man" {...props}></Icon>
