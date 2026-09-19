<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy5qbz8-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qy5qbz8-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:rockylinux-wordmark" {...props}></Icon>
