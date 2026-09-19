<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4cirqb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4cirqb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-down-left-stroke-square-filled" {...props}></Icon>
