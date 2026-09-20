<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u98105u5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="u98105u5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-crouching-wearing-backpack-and-headlamp" {...props}></Icon>
