<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tob-p7yon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tob-p7yon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:internet-explorer" {...props}></Icon>
