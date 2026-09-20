<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukyr80b4m.css';
import '../../css/z/zbs1n8-tz.css';
import '../../css/y/yynvv2qce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ukyr80b4m"/><path class="zbs1n8-tz"/><path class="yynvv2qce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:cassette-tape" {...props}></Icon>
