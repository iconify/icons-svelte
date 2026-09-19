<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7v76fbki.css';
import '../../css/u/u-3l03b-a.css';
import '../../css/s/skd9ipjko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z7v76fbki"/><path class="u-3l03b-a"/><path class="skd9ipjko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:hospital" {...props}></Icon>
