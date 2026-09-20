<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er6f_gbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="er6f_gbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:optistack-light" {...props}></Icon>
