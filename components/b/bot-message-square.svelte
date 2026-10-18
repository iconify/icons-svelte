<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybu_i-bqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ybu_i-bqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:bot-message-square" {...props}></Icon>
