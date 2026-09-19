<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah89dicoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ah89dicoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:arrow-down-left" {...props}></Icon>
