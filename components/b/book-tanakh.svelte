<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g36nsd2ec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="g36nsd2ec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:book-tanakh" {...props}></Icon>
