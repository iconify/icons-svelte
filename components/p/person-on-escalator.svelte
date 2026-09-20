<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6y99-9zm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y6y99-9zm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-on-escalator" {...props}></Icon>
