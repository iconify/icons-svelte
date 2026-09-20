<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eau1cd7mu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eau1cd7mu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:conslee-dark" {...props}></Icon>
