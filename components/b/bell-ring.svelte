<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygui90b_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygui90b_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bell-ring" {...props}></Icon>
