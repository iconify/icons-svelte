<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0yhf0b6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="o0yhf0b6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:black-left-double-triangle-filled" {...props}></Icon>
