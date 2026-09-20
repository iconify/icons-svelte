<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6l_-lb6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x6l_-lb6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bowling" {...props}></Icon>
