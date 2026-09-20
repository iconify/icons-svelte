<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do20yoj7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="do20yoj7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:moon-sleep" {...props}></Icon>
