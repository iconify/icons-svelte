<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo58ugbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eo58ugbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:chevron-down" {...props}></Icon>
