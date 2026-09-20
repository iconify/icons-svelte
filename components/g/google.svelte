<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ts_urt4hp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ts_urt4hp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:google" {...props}></Icon>
