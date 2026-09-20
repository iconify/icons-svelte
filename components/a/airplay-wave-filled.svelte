<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyvvzzbvp.css';
import '../../css/m/mqf73h98a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hyvvzzbvp"/><path class="mqf73h98a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:airplay-wave-filled" {...props}></Icon>
