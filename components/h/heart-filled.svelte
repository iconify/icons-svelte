<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w22tyrbbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w22tyrbbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:heart-filled" {...props}></Icon>
