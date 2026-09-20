<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iepnh6q-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iepnh6q-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:car" {...props}></Icon>
