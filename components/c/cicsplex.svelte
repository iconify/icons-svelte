<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy2kxn1ne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oy2kxn1ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cicsplex" {...props}></Icon>
