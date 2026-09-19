<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2nbqq6me.css';
import '../../css/k/k2czn9xff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w2nbqq6me"/><path class="k2czn9xff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:checkbox-checked" {...props}></Icon>
