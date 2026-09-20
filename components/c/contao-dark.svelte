<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlop-v64y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tlop-v64y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:contao-dark" {...props}></Icon>
