<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhdehmbmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhdehmbmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:push-chevron-up" {...props}></Icon>
