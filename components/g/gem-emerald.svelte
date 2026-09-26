<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urt65zqpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="urt65zqpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:gem-emerald" {...props}></Icon>
