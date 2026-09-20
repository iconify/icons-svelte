<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoc4ocbwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xoc4ocbwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:border-inner" {...props}></Icon>
