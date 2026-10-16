<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn313-bdo.css';
import '../../css/c/cw3ksvblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fn313-bdo"/><path class="cw3ksvblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:landfill-gas-48" {...props}></Icon>
