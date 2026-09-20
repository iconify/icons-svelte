<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcneon1wc.css';
import '../../css/f/fdawbm_9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dcneon1wc"/><path class="fdawbm_9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bath-solid" {...props}></Icon>
