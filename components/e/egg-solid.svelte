<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsfwnr_ph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bsfwnr_ph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:egg-solid" {...props}></Icon>
