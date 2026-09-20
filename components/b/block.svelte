<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkj_rzrox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkj_rzrox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:block" {...props}></Icon>
