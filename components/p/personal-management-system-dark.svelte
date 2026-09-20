<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr964_uzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yr964_uzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:personal-management-system-dark" {...props}></Icon>
