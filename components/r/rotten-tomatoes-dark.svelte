<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybks5f9jf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ybks5f9jf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rotten-tomatoes-dark" {...props}></Icon>
