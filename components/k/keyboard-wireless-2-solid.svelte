<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjidu3bgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cjidu3bgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:keyboard-wireless-2-solid" {...props}></Icon>
