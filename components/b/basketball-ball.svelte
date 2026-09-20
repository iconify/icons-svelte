<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aizo16bry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aizo16bry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:basketball-ball" {...props}></Icon>
