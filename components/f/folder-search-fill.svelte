<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsz0ddbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wsz0ddbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-search-fill" {...props}></Icon>
