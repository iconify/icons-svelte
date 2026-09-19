<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snfd_jbqj.css';
import '../../css/d/d7v_hcc-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="snfd_jbqj"/><path class="d7v_hcc-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:pricetag-outline" {...props}></Icon>
