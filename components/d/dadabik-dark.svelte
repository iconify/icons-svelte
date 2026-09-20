<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj8w24brh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wj8w24brh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dadabik-dark" {...props}></Icon>
