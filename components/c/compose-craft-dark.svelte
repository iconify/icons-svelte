<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2m6gubxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m2m6gubxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:compose-craft-dark" {...props}></Icon>
