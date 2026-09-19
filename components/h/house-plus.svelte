<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lui1zkh6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lui1zkh6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:house-plus" {...props}></Icon>
