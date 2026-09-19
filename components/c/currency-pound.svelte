<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfe5p0b6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xfe5p0b6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:currency-pound" {...props}></Icon>
