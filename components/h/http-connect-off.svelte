<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2wdr2ceg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c2wdr2ceg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:http-connect-off" {...props}></Icon>
