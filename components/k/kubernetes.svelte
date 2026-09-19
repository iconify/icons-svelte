<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9i_9xbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e9i_9xbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:kubernetes" {...props}></Icon>
