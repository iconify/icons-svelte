<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8-2fsnql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a8-2fsnql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:filen" {...props}></Icon>
