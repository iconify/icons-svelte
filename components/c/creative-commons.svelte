<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c33ymtb-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":488};
const content = `<path class="c33ymtb-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:creative-commons" {...props}></Icon>
