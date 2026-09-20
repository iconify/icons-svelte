<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pegkd7mar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pegkd7mar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:reorder-filled" {...props}></Icon>
