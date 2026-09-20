<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooyh4zckz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ooyh4zckz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:palmr-dark" {...props}></Icon>
