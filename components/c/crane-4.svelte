<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1ck9ujgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="v1ck9ujgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:crane-4" {...props}></Icon>
