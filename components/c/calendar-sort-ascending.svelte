<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmum_5bij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmum_5bij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:calendar-sort-ascending" {...props}></Icon>
