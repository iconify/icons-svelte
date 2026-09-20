<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iiqrs_neo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iiqrs_neo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-imac-dollar" {...props}></Icon>
