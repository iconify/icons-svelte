<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak8qh_69j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ak8qh_69j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:axis-x-rotate-counterclockwise" {...props}></Icon>
