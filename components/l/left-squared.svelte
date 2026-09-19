<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh3ac30pt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wh3ac30pt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:left-squared" {...props}></Icon>
