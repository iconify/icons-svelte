<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7p3bhbop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7p3bhbop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:picture-frame-filled" {...props}></Icon>
