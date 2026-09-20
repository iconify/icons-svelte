<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z31lnrbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z31lnrbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:coin-fill" {...props}></Icon>
