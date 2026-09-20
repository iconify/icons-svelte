<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu3t20bdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xu3t20bdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:diagram-split-horizontal-bold" {...props}></Icon>
