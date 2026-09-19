<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl1ct9w7i.css';
import '../../css/c/cpisrvb2h.css';
import '../../css/z/z2jaifrlq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dl1ct9w7i"/><path class="cpisrvb2h"/><path class="z2jaifrlq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-bowtie" {...props}></Icon>
