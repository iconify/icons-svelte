<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osb4_j5yq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="osb4_j5yq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:franca" {...props}></Icon>
