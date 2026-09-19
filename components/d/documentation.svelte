<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdzot4buc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vdzot4buc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:documentation" {...props}></Icon>
