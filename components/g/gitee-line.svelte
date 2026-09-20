<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew1-g2bgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ew1-g2bgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:gitee-line" {...props}></Icon>
