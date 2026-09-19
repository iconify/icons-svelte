<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igu2c5bmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="igu2c5bmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:medium-m" {...props}></Icon>
