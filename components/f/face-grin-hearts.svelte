<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozvx3qbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ozvx3qbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:face-grin-hearts" {...props}></Icon>
