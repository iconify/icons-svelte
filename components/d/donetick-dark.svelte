<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jao-hnd7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jao-hnd7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:donetick-dark" {...props}></Icon>
