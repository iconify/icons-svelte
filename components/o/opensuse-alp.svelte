<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uob9tnnhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uob9tnnhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opensuse-alp" {...props}></Icon>
