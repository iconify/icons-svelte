<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zueh1cegf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zueh1cegf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:fitbit-logo" {...props}></Icon>
