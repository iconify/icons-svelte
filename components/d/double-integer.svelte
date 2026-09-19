<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6c2xkbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e6c2xkbwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:double-integer" {...props}></Icon>
