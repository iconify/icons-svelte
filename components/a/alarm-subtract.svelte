<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsubc8bso.css';
import '../../css/b/b3wbj4but.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vsubc8bso"/><path class="b3wbj4but"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:alarm-subtract" {...props}></Icon>
