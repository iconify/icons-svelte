<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp8cedcrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tp8cedcrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:alexandrie-light" {...props}></Icon>
