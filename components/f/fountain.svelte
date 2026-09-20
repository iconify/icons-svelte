<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oas2c_bnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oas2c_bnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:fountain" {...props}></Icon>
