<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nox49tb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nox49tb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-auto" {...props}></Icon>
