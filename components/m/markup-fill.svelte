<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg3wgt3ac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yg3wgt3ac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:markup-fill" {...props}></Icon>
