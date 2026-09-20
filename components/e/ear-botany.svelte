<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf7gmnyim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cf7gmnyim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:ear-botany" {...props}></Icon>
