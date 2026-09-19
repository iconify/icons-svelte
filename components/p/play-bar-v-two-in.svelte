<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rucr588rq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rucr588rq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:play-bar-v-two-in" {...props}></Icon>
