<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0mwdubax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0mwdubax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:presentation-2-fill" {...props}></Icon>
