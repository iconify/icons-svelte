<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enc17mb1s.css';
import '../../css/l/l7hcm5_mu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="enc17mb1s"/><path class="l7hcm5_mu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:next" {...props}></Icon>
