<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7zp-dbvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x7zp-dbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:paragraph-9" {...props}></Icon>
