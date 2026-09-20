<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq-2blb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xq-2blb_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:leaf-3-line" {...props}></Icon>
