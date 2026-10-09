<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swnxxbo0p.css';
import '../../css/l/l4yoqg4nl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="swnxxbo0p"/><path class="l4yoqg4nl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:capacity-20" {...props}></Icon>
