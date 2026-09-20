<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvtw_wblv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mvtw_wblv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:debian" {...props}></Icon>
