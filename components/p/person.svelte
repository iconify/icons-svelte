<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knbz9_b2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="knbz9_b2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:person" {...props}></Icon>
