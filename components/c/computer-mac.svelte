<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg_zwb-4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mg_zwb-4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:computer-mac" {...props}></Icon>
