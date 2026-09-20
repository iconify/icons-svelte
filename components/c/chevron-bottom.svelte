<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz945htqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="kz945htqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:chevron-bottom" {...props}></Icon>
