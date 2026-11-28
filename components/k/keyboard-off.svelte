<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/is8gm10_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="is8gm10_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:keyboard-off" {...props}></Icon>
