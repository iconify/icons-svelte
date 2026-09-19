<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac-3z-sub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ac-3z-sub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:automatic" {...props}></Icon>
