<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gn99un74y.css';
import '../../css/p/pzu7n0f2i.css';
import '../../css/v/vko700nqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="gn99un74y"/><path class="pzu7n0f2i"/><path class="vko700nqz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:oncoming-fist" {...props}></Icon>
