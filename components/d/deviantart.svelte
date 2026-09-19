<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-2ebz4el.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-2ebz4el"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:deviantart" {...props}></Icon>
