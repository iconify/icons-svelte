<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz4wp-bec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lz4wp-bec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:punctuation-check" {...props}></Icon>
