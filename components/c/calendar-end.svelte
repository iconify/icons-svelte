<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgh8kzkar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qgh8kzkar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-end" {...props}></Icon>
