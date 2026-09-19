<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikwwh-bte.css';
import '../../css/w/w950tvqcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ikwwh-bte"/><path class="w950tvqcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:fax" {...props}></Icon>
