<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz5c19bcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uz5c19bcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrows-transfer-up" {...props}></Icon>
