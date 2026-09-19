<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bfv-mo1dy.css';
import '../../css/n/n0rf62bgo.css';
import '../../css/c/c1xidzbgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="bfv-mo1dy"/><path class="n0rf62bgo"/><path class="c1xidzbgj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:reminder-ribbon" {...props}></Icon>
