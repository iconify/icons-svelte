<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnyxcvboq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="lnyxcvboq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-up-right-box" {...props}></Icon>
