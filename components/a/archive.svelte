<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft9sjzb0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ft9sjzb0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:archive" {...props}></Icon>
