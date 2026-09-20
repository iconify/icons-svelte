<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty2v0klct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ty2v0klct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:location-check-solid" {...props}></Icon>
