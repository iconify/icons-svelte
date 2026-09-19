<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz_reeb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tz_reeb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:flag-checkered" {...props}></Icon>
