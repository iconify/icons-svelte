<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf2qkybtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sf2qkybtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:door-closed-locked-fill" {...props}></Icon>
