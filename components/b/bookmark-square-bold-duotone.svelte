<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcid6acgw.css';
import '../../css/y/yt8zcm-qf.css';
import '../../css/j/jait5vasr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcid6acgw"/><path class="yt8zcm-qf"/><path class="jait5vasr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bookmark-square-bold-duotone" {...props}></Icon>
