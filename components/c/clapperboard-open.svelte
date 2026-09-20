<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js69wbbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="js69wbbuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clapperboard-open" {...props}></Icon>
