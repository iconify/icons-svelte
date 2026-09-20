<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aesz2cvoz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="aesz2cvoz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:expand-right" {...props}></Icon>
