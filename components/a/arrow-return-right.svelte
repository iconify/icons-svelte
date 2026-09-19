<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcmfr-b4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lcmfr-b4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-return-right" {...props}></Icon>
