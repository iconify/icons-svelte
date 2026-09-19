<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfij4xb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="kfij4xb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:h-4-duo" {...props}></Icon>
