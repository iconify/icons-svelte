<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t20u6eccm.css';
import '../../css/y/yrtryqu9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t20u6eccm"/><path class="yrtryqu9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-microphone" {...props}></Icon>
