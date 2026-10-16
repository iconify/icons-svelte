<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k--qs-afs.css';
import '../../css/w/wtt-7nbfn.css';
import '../../css/f/fzdecdctz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k--qs-afs"/><path class="wtt-7nbfn"/><path class="fzdecdctz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rake-20-bold" {...props}></Icon>
