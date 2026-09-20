<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyw9u8buj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oyw9u8buj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:keyboard-off" {...props}></Icon>
