<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdfn_0okk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdfn_0okk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hand-wave-outline" {...props}></Icon>
