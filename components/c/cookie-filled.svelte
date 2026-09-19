<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym1fg2b7s.css';
import '../../css/q/qmopwkg8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ym1fg2b7s"/><path class="qmopwkg8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cookie-filled" {...props}></Icon>
