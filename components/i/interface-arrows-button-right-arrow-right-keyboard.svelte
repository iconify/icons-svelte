<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee5hpnb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ee5hpnb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-button-right-arrow-right-keyboard" {...props}></Icon>
