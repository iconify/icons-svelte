<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsx3c6bcc.css';
import '../../css/e/elgr7ftla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qsx3c6bcc"/><path class="elgr7ftla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:messages-people-user-bubble-circle-bold" {...props}></Icon>
