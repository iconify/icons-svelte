<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_362bcck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="w_362bcck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:laugh-squint" {...props}></Icon>
