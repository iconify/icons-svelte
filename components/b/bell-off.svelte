<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzr7qwbgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jzr7qwbgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:bell-off" {...props}></Icon>
