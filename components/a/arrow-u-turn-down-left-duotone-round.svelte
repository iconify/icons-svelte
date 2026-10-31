<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol3ka2byx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ol3ka2byx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-u-turn-down-left-duotone-round" {...props}></Icon>
