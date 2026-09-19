<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk4gz-bbp.css';
import '../../css/a/afn_zrbzk.css';
import '../../css/v/vcstj9lyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vk4gz-bbp"/><path class="afn_zrbzk"/><path class="vcstj9lyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-notifications-off" {...props}></Icon>
