<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2h23__hx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2h23__hx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mail-warning-line" {...props}></Icon>
