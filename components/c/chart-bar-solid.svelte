<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpyix5bgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpyix5bgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chart-bar-solid" {...props}></Icon>
