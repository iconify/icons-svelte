<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbyi2ub1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kbyi2ub1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:layout-window-11-solid" {...props}></Icon>
