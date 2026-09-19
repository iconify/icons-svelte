<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7ndexc2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7ndexc2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:nest-js" {...props}></Icon>
