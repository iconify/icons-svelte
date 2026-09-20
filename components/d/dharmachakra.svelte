<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m304hzeot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m304hzeot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:dharmachakra" {...props}></Icon>
