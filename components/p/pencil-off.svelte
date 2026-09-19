<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wafrj7bth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wafrj7bth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pencil-off" {...props}></Icon>
