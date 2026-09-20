<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwntxgpss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwntxgpss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:euro-diamond-solid" {...props}></Icon>
