<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp0xepb8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wp0xepb8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:keyboard-x" {...props}></Icon>
