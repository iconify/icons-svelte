<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8x-36bon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="e8x-36bon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:ello" {...props}></Icon>
