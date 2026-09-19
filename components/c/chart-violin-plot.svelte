<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgpzimtyu.css';
import '../../css/b/b3jg8vbmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hgpzimtyu"/><path class="b3jg8vbmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-violin-plot" {...props}></Icon>
