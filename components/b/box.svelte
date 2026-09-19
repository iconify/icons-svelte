<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5nx49f4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="g5nx49f4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:box" {...props}></Icon>
