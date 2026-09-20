<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inrh0cprn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="inrh0cprn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mealie-dark" {...props}></Icon>
