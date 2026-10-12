<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4slh4bwa.css';
import '../../css/k/kh5w1ccnj.css';
import '../../css/s/sh06c0bcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w4slh4bwa"/><path class="kh5w1ccnj"/><path class="sh06c0bcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:power-station-check-20-bold" {...props}></Icon>
