<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puzoi6ljd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="puzoi6ljd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:rain" {...props}></Icon>
