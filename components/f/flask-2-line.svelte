<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zup424bdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zup424bdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flask-2-line" {...props}></Icon>
