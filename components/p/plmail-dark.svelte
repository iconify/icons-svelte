<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zimgv8bvk.css';
import '../../css/c/cudl-bmyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zimgv8bvk"/><path class="cudl-bmyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:plmail-dark" {...props}></Icon>
