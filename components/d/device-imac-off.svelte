<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2kxynban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2kxynban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-imac-off" {...props}></Icon>
