<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hmrtfwbyk.css';
import '../../css/o/omua7k0ch.css';
import '../../css/f/fgxrb3bou.css';
import '../../css/h/hw1lekbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="hmrtfwbyk"/><path class="omua7k0ch"/><path class="fgxrb3bou"/><path class="hw1lekbqa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:flying-disc" {...props}></Icon>
