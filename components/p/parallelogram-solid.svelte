<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ga7_-ybll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ga7_-ybll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:parallelogram-solid" {...props}></Icon>
