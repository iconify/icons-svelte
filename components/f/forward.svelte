<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd22b9x_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pd22b9x_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:forward" {...props}></Icon>
