<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhigi9b0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhigi9b0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:messages" {...props}></Icon>
