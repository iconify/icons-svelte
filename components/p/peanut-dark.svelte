<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdbh8k3zh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vdbh8k3zh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:peanut-dark" {...props}></Icon>
