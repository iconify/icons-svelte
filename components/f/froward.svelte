<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mce7bcylo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mce7bcylo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:froward" {...props}></Icon>
