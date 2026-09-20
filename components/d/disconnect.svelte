<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ju513l7dl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ju513l7dl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:disconnect" {...props}></Icon>
