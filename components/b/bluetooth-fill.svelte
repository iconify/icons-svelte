<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvwshjnyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bvwshjnyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bluetooth-fill" {...props}></Icon>
