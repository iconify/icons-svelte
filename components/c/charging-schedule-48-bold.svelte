<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0rqam1_z.css';
import '../../css/q/qjd9f8_8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a0rqam1_z"/><path class="qjd9f8_8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charging-schedule-48-bold" {...props}></Icon>
