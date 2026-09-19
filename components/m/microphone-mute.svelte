<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru4yxcipc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ru4yxcipc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:microphone-mute" {...props}></Icon>
