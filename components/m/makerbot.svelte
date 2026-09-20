<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy71hobft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oy71hobft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:makerbot" {...props}></Icon>
