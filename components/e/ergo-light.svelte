<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s568gputr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s568gputr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ergo-light" {...props}></Icon>
