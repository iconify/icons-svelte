<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzwzl0bzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hzwzl0bzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lightbulb-48" {...props}></Icon>
