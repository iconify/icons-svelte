<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htrmvrbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="htrmvrbjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:clovalink-dark" {...props}></Icon>
