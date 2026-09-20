<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk21khipp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tk21khipp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:loaf-of-bread-above-outstretched-hand" {...props}></Icon>
