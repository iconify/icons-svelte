<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjjyz8b6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vjjyz8b6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-radio-button-off" {...props}></Icon>
