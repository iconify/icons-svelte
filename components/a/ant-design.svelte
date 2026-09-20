<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvv5p-omy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvv5p-omy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ant-design" {...props}></Icon>
