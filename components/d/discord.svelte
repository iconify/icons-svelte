<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi4ovhblm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xi4ovhblm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:discord" {...props}></Icon>
