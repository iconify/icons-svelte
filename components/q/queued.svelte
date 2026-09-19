<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1nqv73bw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y1nqv73bw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:queued" {...props}></Icon>
