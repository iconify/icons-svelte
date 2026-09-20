<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-yb6znrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f-yb6znrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:poznote-light" {...props}></Icon>
