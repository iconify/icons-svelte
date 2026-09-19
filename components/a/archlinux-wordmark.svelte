<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1pbj0p4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="x1pbj0p4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:archlinux-wordmark" {...props}></Icon>
