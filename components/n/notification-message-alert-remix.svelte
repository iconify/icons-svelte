<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4i95ksyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r4i95ksyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:notification-message-alert-remix" {...props}></Icon>
