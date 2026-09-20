<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz3eg4bhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oz3eg4bhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:level-left-bold" {...props}></Icon>
