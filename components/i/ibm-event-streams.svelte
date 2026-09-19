<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7w-pxplo.css';
import '../../css/i/iv1cdqgvk.css';
import '../../css/n/n7mqk6l-u.css';
import '../../css/t/tayf2v4-u.css';
import '../../css/k/k39_n0lox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b7w-pxplo"/><circle class="iv1cdqgvk"/><path class="n7mqk6l-u"/><circle class="tayf2v4-u"/><path class="k39_n0lox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-event-streams" {...props}></Icon>
