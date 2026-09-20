<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srfomyb-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="srfomyb-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:h6" {...props}></Icon>
