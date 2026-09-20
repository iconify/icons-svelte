<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzsz6cbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mzsz6cbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-shoveling-dirt" {...props}></Icon>
