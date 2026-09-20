<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d63o6h2ho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d63o6h2ho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:khoj-dark" {...props}></Icon>
