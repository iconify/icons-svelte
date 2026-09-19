<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l44h7xbjy.css';
import '../../css/d/dc_a__mcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g transform="translate(32 0) scale(-1 1)"><g class="ft5dv1b6b"><path class="l44h7xbjy"/><path class="dc_a__mcz"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:backhand-index-pointing-right-light" {...props}></Icon>
