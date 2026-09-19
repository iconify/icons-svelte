<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlpp7qqxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zlpp7qqxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chevron-right" {...props}></Icon>
