<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/o/of4w63b2b.css';
import '../../css/o/o-kwjpbjy.css';
import '../../css/i/iulpltu0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="of4w63b2b"/><path class="o-kwjpbjy"/><path class="iulpltu0r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cash-01" {...props}></Icon>
