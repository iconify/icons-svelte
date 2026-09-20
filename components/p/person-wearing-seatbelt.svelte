<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6d83mbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="w6d83mbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-wearing-seatbelt" {...props}></Icon>
