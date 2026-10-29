<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muqvk_xvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="muqvk_xvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:phone" {...props}></Icon>
