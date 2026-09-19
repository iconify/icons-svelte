<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emy61w2gd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="emy61w2gd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:ellipse" {...props}></Icon>
