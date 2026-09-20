<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhdvo6bir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uhdvo6bir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:burger" {...props}></Icon>
