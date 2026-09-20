<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn402ibbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mn402ibbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:moon-fill" {...props}></Icon>
