<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg5b9ebia.css';
import '../../css/h/hrfcglb8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yg5b9ebia"/><path class="hrfcglb8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bell-snooze-48-bold" {...props}></Icon>
