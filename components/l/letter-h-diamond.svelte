<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t39vyu_8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t39vyu_8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-h-diamond" {...props}></Icon>
