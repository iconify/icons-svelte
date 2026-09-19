<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1un75b3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f1un75b3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:icq" {...props}></Icon>
