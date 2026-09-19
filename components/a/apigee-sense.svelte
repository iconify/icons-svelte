<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttatuib8i.css';
import '../../css/j/jdr9a7bii.css';
import '../../css/l/l04bb08wk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ttatuib8i"/><path class="jdr9a7bii"/><path class="l04bb08wk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:apigee-sense" {...props}></Icon>
