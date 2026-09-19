<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn3g4qbds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sn3g4qbds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pacifism" {...props}></Icon>
