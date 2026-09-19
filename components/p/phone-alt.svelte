<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjq2_lbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bjq2_lbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:phone-alt" {...props}></Icon>
