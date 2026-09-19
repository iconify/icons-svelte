<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bflich7ut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="bflich7ut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:korvue" {...props}></Icon>
