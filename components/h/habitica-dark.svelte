<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unyc-m8wb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="unyc-m8wb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:habitica-dark" {...props}></Icon>
