<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-226492u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-226492u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:pill-x" {...props}></Icon>
