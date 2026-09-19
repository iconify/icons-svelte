<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezcvdga6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ezcvdga6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logo-youtube" {...props}></Icon>
