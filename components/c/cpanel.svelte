<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhqvjfb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="dhqvjfb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:cpanel" {...props}></Icon>
