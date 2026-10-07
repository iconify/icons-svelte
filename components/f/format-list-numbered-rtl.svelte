<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/m3q5dgd3j.css';
import '../../css/z/z5isr3bvu.css';
import '../../css/c/ce7yr5b1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="m3q5dgd3j"/><path class="z5isr3bvu"/><path class="ce7yr5b1g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:format-list-numbered-rtl" {...props}></Icon>
