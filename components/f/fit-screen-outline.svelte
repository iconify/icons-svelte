<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpes_5kab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kpes_5kab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:fit-screen-outline" {...props}></Icon>
