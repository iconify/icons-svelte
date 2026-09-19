<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9qymsk4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="y9qymsk4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:glass-cheers" {...props}></Icon>
