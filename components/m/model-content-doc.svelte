<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6ajanxdn.css';
import '../../css/b/b1_a9z27d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f6ajanxdn"/><path class="b1_a9z27d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:model-content-doc" {...props}></Icon>
