<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oidz_-bbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oidz_-bbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-sql-server-light" {...props}></Icon>
