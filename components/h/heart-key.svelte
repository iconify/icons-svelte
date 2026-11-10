<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqytxs1ph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqytxs1ph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:heart-key" {...props}></Icon>
