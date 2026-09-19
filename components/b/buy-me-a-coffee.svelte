<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqqtwhrrx.css';
import '../../css/z/zgm2r3bvm.css';
import '../../css/n/nm2dyfd2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqqtwhrrx"/><path class="zgm2r3bvm"/><path class="nm2dyfd2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:buy-me-a-coffee" {...props}></Icon>
