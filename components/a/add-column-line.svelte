<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwkhe_-2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwkhe_-2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:add-column-line" {...props}></Icon>
