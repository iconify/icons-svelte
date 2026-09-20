<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rafsg0atz.css';
import '../../css/w/wn36-3bgk.css';
import '../../css/k/k7_ztobeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rafsg0atz"/><path class="wn36-3bgk"/><path class="k7_ztobeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bmw" {...props}></Icon>
