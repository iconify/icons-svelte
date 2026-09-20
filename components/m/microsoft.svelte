<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir5c0ly1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ir5c0ly1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:microsoft" {...props}></Icon>
