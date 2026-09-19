<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0s--2bfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m0s--2bfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:confused" {...props}></Icon>
