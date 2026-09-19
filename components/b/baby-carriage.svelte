<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqsm664nr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eqsm664nr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:baby-carriage" {...props}></Icon>
