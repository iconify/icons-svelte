<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsmhpgwcs.css';
import '../../css/c/c_1sw_nww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tsmhpgwcs"/><path class="c_1sw_nww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:picture-in-picture-48" {...props}></Icon>
