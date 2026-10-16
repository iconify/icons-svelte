<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km_1fum4q.css';
import '../../css/s/s45evebmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="km_1fum4q"/><path class="s45evebmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heating-schedule-48" {...props}></Icon>
