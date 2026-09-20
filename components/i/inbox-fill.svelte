<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-2ra_b2r.css';
import '../../css/s/sjfm5_b1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-2ra_b2r"/><path class="sjfm5_b1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:inbox-fill" {...props}></Icon>
