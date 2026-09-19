<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4uk8wrue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="h4uk8wrue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:alarm-snooze" {...props}></Icon>
