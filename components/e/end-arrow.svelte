<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/galb7gc_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="galb7gc_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:end-arrow" {...props}></Icon>
