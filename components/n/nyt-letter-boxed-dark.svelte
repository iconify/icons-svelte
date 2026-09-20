<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze_ex8o5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ze_ex8o5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nyt-letter-boxed-dark" {...props}></Icon>
