<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jis16yg7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jis16yg7o primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:droplet-duotone" {...props}></Icon>
