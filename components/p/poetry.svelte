<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z92us65vz.css';
import '../../css/r/ruzjusbdh.css';
import '../../css/i/i-v3skr5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z92us65vz"/><path class="ruzjusbdh"/><path class="i-v3skr5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:poetry" {...props}></Icon>
