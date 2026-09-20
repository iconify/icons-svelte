<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw6ug9bey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nw6ug9bey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:countdown-timer-remix" {...props}></Icon>
