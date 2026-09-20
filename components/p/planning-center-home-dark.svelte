<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x683x7b4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x683x7b4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:planning-center-home-dark" {...props}></Icon>
