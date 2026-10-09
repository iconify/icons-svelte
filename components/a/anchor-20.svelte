<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbtvgabzb.css';
import '../../css/i/igsxkccpo.css';
import '../../css/l/lybvyzwhf.css';
import '../../css/v/vseb-gbvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rbtvgabzb"/><path class="igsxkccpo"/><path class="lybvyzwhf"/><path class="vseb-gbvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:anchor-20" {...props}></Icon>
