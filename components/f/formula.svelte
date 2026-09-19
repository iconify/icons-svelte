<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbej-b2vl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lbej-b2vl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:formula" {...props}></Icon>
