<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v26w1ttai.css';
import '../../css/h/hbqtujzwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v26w1ttai"/><path class="hbqtujzwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fries-48-bold" {...props}></Icon>
