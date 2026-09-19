<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w25h46bvy.css';
import '../../css/f/fuqf47bsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w25h46bvy"/><path class="fuqf47bsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:flag-chequered-filled" {...props}></Icon>
