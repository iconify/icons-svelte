<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hwedgwb1d.css';
import '../../css/z/zn0m79bnw.css';
import '../../css/o/o8y35xbbr.css';
import '../../css/t/tq8vc0lgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="hwedgwb1d"/><path class="zn0m79bnw"/><path class="o8y35xbbr"/><path class="tq8vc0lgj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:elephant" {...props}></Icon>
