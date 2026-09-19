<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfgm4ibzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b gfgm4ibzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:apps-alt-filled" {...props}></Icon>
