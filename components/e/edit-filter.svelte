<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8ucuebqy.css';
import '../../css/t/t-aq49b1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x8ucuebqy"/><path class="t-aq49b1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:edit-filter" {...props}></Icon>
