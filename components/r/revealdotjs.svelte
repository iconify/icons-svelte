<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr7qnfbqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rr7qnfbqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:revealdotjs" {...props}></Icon>
