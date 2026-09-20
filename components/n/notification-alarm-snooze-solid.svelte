<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud109lbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ud109lbcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:notification-alarm-snooze-solid" {...props}></Icon>
