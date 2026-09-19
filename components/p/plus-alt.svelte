<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8_nnsy-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i8_nnsy-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:plus-alt" {...props}></Icon>
