<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4-_1ab-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1792};
const content = `<path class="l4-_1ab-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:calculator" {...props}></Icon>
