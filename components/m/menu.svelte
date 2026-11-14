<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btwgxibgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="btwgxibgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:menu" {...props}></Icon>
