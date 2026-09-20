<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/een_dgbbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="een_dgbbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:fat-arrow-down-solid" {...props}></Icon>
