<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq_eunbvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lq_eunbvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:maximize-16" {...props}></Icon>
