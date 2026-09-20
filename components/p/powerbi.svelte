<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yowci5pvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yowci5pvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:powerbi" {...props}></Icon>
