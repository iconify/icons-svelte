<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmwzwvbuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vmwzwvbuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-2" {...props}></Icon>
