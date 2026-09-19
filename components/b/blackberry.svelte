<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5gky4bwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z5gky4bwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:blackberry" {...props}></Icon>
