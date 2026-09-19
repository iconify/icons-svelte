<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipl4zsbbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ipl4zsbbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:component" {...props}></Icon>
