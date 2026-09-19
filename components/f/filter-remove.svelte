<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqjus3b5f.css';
import '../../css/c/ch2vo1b_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uqjus3b5f"/><path class="ch2vo1b_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:filter-remove" {...props}></Icon>
