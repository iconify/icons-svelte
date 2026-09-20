<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0_7kqbds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="h0_7kqbds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:houseboat-on-water" {...props}></Icon>
