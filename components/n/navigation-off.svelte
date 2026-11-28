<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5hxohfba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5hxohfba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:navigation-off" {...props}></Icon>
