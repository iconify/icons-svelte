<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty9awnngf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ty9awnngf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:book" {...props}></Icon>
