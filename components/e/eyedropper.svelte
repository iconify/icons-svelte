<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2jokr2vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g2jokr2vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:eyedropper" {...props}></Icon>
