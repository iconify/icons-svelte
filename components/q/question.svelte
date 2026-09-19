<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9t0j1b_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":928,"height":1280};
const content = `<path class="s9t0j1b_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:question" {...props}></Icon>
