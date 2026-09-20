<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n399bo9an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n399bo9an"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:graph-bar" {...props}></Icon>
