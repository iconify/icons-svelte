<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzwl35boe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dzwl35boe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:filter-2-discount" {...props}></Icon>
