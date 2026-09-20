<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4bmzvb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="a4bmzvb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:notification-alarm-snooze-remix" {...props}></Icon>
