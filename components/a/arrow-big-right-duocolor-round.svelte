<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knu0x1b-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knu0x1b-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-big-right-duocolor-round" {...props}></Icon>
