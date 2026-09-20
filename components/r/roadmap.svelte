<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8rd_rbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8rd_rbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:roadmap" {...props}></Icon>
