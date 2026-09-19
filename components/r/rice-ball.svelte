<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lfo9zmb1i.css';
import '../../css/w/w0icurbfp.css';
import '../../css/k/kv9lyjb2a.css';
import '../../css/e/e7eydrofg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="lfo9zmb1i"/><path class="w0icurbfp"/><path class="kv9lyjb2a"/><path class="e7eydrofg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:rice-ball" {...props}></Icon>
