<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzwzl0bzs.css';
import '../../css/t/te6at6blm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hzwzl0bzs"/><path class="te6at6blm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lightbulb-sparkle-48" {...props}></Icon>
