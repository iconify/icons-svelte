<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot32r4bbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ot32r4bbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:dots-hexagon-solid" {...props}></Icon>
