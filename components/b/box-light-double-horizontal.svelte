<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa2kh1q4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="sa2kh1q4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-double-horizontal" {...props}></Icon>
