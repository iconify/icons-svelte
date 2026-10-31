<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1_05pxtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1_05pxtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-u-turn-right-down-duocolor-round" {...props}></Icon>
