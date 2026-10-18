<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uoujtnlpy.css';
import '../../css/c/cso2t9k2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uoujtnlpy"/><path class="cso2t9k2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:expansion-vessel-48-bold" {...props}></Icon>
