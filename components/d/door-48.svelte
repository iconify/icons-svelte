<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wifw4mbzo.css';
import '../../css/j/j5rik_bqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wifw4mbzo"/><path class="j5rik_bqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:door-48" {...props}></Icon>
