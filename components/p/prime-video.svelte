<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w038znbwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w038znbwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:prime-video" {...props}></Icon>
