<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odrt_7b6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="odrt_7b6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:funnel-sort" {...props}></Icon>
