<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8xbdfbrh.css';
import '../../css/h/hok4abbfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v8xbdfbrh"/><path class="hok4abbfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:history-48" {...props}></Icon>
