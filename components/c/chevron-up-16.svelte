<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6u-qcq3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y6u-qcq3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:chevron-up-16" {...props}></Icon>
