<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w79r3bb5w.css';
import '../../css/b/btzvfmb9o.css';
import '../../css/s/sh06c0bcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w79r3bb5w"/><path class="btzvfmb9o"/><path class="sh06c0bcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bell-check-20-bold" {...props}></Icon>
