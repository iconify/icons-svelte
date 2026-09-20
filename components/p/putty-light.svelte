<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-zny-e6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u-zny-e6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:putty-light" {...props}></Icon>
