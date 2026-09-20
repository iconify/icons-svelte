<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfs826bwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfs826bwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:palette-filled" {...props}></Icon>
