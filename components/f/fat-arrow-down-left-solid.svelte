<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjqu0sf-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjqu0sf-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:fat-arrow-down-left-solid" {...props}></Icon>
