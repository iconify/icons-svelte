<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtm8-702u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtm8-702u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:audio" {...props}></Icon>
