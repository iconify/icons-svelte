<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whrvg9bit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="whrvg9bit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:razer" {...props}></Icon>
