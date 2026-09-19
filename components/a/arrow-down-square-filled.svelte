<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w41mwubps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w41mwubps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-down-square-filled" {...props}></Icon>
