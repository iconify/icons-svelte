<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0g9_xl5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0g9_xl5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:briefcase-conveyor-belt" {...props}></Icon>
