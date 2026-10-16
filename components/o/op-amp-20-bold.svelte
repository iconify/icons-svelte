<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za0t5mbix.css';
import '../../css/k/kve0vpbry.css';
import '../../css/g/gely41auh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="za0t5mbix"/><path class="kve0vpbry"/><path class="gely41auh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:op-amp-20-bold" {...props}></Icon>
