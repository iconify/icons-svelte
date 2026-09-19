<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl933tb7k.css';
import '../../css/s/s-5hvuboc.css';
import '../../css/k/k68b7sadh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fl933tb7k"/><path class="s-5hvuboc"/><path class="k68b7sadh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:library" {...props}></Icon>
