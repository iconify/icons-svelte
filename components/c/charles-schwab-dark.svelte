<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbzvq011k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gbzvq011k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:charles-schwab-dark" {...props}></Icon>
