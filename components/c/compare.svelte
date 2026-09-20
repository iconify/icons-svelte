<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kre_v31nh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="kre_v31nh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:compare" {...props}></Icon>
