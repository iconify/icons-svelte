<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjpy3bcjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjpy3bcjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:align-left-solid" {...props}></Icon>
