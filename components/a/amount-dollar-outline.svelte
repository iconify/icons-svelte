<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phbhwfbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="phbhwfbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:amount-dollar-outline" {...props}></Icon>
