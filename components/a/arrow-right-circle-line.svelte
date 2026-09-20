<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxouw4mds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxouw4mds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:arrow-right-circle-line" {...props}></Icon>
