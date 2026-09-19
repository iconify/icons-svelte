<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/e4i3ki2pe.css';
import '../../css/v/v_hbrccao.css';
import '../../css/z/z21ut7bfm.css';
import '../../css/k/krj2or7of.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="e4i3ki2pe"/><path class="v_hbrccao"/><path class="z21ut7bfm"/><path class="krj2or7of"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:calendar" {...props}></Icon>
