<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mh6cbej9q.css';
import '../../css/s/shfkwhm7d.css';
import '../../css/t/thyp_qbyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="mh6cbej9q"/><path class="shfkwhm7d"/><path class="thyp_qbyh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:long-drum" {...props}></Icon>
