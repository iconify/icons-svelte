<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv9yunb2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="yv9yunb2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:check-badge-stroke-12" {...props}></Icon>
