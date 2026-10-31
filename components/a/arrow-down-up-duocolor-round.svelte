<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci3t7cxvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ci3t7cxvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-down-up-duocolor-round" {...props}></Icon>
