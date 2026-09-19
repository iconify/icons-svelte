<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic2j-qb0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ic2j-qb0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:note-sticky" {...props}></Icon>
