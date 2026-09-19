<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c5muhfx1s.css';
import '../../css/m/md286fbip.css';
import '../../css/z/z2q6q0i8u.css';
import '../../css/h/had8mlbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="c5muhfx1s"/><g class="md286fbip"><path class="z2q6q0i8u"/><path class="had8mlbwn"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:ray" {...props}></Icon>
