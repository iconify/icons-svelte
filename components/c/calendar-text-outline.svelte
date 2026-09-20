<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6vjzl3ay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6vjzl3ay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-text-outline" {...props}></Icon>
