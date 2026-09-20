<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tja7qfb6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tja7qfb6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:number-filled" {...props}></Icon>
