<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksutv4lbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksutv4lbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-turn-left-up-duocolor-round" {...props}></Icon>
