<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx7io3l3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vx7io3l3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-standing-wearing-dress-beside-divider-beside-broadshouldered-person-standing" {...props}></Icon>
