<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzcd-gs6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="nzcd-gs6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:headphones" {...props}></Icon>
