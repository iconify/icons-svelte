<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csk5pbt9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="csk5pbt9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:patreon" {...props}></Icon>
