<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3hq6lb8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z3hq6lb8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:lightbulb" {...props}></Icon>
