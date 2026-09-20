<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh602ub6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gh602ub6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:picture-in-picture-bottom-right-outline" {...props}></Icon>
