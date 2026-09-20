<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxa326maf.css';
import '../../css/r/r7uozib3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lxa326maf"/><path class="r7uozib3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:preview-circle-fill" {...props}></Icon>
