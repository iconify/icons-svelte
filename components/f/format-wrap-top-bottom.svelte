<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxhqgb70j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxhqgb70j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-wrap-top-bottom" {...props}></Icon>
