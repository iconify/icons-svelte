<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah44nkblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ah44nkblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:rotate" {...props}></Icon>
