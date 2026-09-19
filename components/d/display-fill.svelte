<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7_7_qmrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w7_7_qmrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:display-fill" {...props}></Icon>
