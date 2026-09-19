<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/va3b78biq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="va3b78biq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-dictionary" {...props}></Icon>
