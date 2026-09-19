<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfe3hlzex.css';
import '../../css/n/ncinpdbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kfe3hlzex"/><path class="ncinpdbjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:mouth-slash" {...props}></Icon>
