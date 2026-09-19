<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-33urxjf.css';
import '../../css/v/v0dunlvta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-33urxjf"/><path class="v0dunlvta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-down-left-stroke-square-filled" {...props}></Icon>
