<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r36e_8bxp.css';
import '../../css/m/mfr2nesuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r36e_8bxp"/><path class="mfr2nesuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:browse-off-filled" {...props}></Icon>
