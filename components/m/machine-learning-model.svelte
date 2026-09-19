<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqj-0svkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kqj-0svkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:machine-learning-model" {...props}></Icon>
