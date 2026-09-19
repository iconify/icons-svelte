<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8wlhdb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q8wlhdb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:eyedropper" {...props}></Icon>
