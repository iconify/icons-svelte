<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpv7c9bnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jpv7c9bnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chirpstack" {...props}></Icon>
