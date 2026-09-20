<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv_4-pb7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vv_4-pb7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:atm" {...props}></Icon>
