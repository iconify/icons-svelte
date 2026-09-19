<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgj8co51w.css';
import '../../css/s/slueoubbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kgj8co51w"/><path class="slueoubbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:checkmark-outline-error" {...props}></Icon>
