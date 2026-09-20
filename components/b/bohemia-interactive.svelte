<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se1bk8kjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="se1bk8kjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bohemia-interactive" {...props}></Icon>
