<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5__nsf_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m5__nsf_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:credit-card-solid" {...props}></Icon>
