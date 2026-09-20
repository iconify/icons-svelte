<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zllir3b7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zllir3b7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:googlestreetview" {...props}></Icon>
