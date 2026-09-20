<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omitv2byq.css';
import '../../css/s/s6gb733yj.css';
import '../../css/g/g1kqfibni.css';
import '../../css/x/xy5e245oe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="omitv2byq"/><path class="s6gb733yj"/><path class="g1kqfibni"/><path class="xy5e245oe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:freecad" {...props}></Icon>
