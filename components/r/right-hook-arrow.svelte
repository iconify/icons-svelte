<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oglcqcc1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="oglcqcc1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:right-hook-arrow" {...props}></Icon>
