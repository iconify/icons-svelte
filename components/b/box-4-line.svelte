<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qibd9rb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qibd9rb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:box-4-line" {...props}></Icon>
