<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhj13ubxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nhj13ubxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:bath" {...props}></Icon>
