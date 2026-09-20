<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpozmrb_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hpozmrb_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:home-x-solid" {...props}></Icon>
