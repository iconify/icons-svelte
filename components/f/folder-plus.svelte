<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhi8vggfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhi8vggfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:folder-plus" {...props}></Icon>
