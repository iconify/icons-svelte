<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb3n8obkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wb3n8obkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-s-down" {...props}></Icon>
