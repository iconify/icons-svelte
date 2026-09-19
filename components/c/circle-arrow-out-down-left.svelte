<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohv39gr8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohv39gr8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:circle-arrow-out-down-left" {...props}></Icon>
