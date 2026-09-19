<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sk8b5jbko.css';
import '../../css/i/ir80l-8id.css';
import '../../css/t/t49aahmwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="sk8b5jbko"/><path class="ir80l-8id"/><path class="t49aahmwu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:ringed-planet" {...props}></Icon>
