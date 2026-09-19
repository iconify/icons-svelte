<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_ci2_etv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d_ci2_etv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:lock-open-16-solid" {...props}></Icon>
