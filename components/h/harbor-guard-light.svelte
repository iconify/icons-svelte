<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfwshp_nm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yfwshp_nm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:harbor-guard-light" {...props}></Icon>
