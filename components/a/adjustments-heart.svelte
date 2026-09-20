<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hey61xy0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hey61xy0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:adjustments-heart" {...props}></Icon>
