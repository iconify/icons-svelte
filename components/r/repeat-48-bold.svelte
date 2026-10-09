<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/feeids0fq.css';
import '../../css/w/whujt0lbg.css';
import '../../css/s/sjk5febne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="feeids0fq"/><path class="whujt0lbg"/><path class="sjk5febne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:repeat-48-bold" {...props}></Icon>
