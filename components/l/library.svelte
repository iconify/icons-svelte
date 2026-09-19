<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/s/s3nyltbvc.css';
import '../../css/p/pi0z5lblf.css';
import '../../css/c/cgmlxbbcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s3nyltbvc"/><path class="pi0z5lblf"/><path class="cgmlxbbcq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:library" {...props}></Icon>
