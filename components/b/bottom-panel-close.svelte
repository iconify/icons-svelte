<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2sco8uze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l2sco8uze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:bottom-panel-close" {...props}></Icon>
