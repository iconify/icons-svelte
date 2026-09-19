<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm6vebhwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="gm6vebhwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:behance" {...props}></Icon>
