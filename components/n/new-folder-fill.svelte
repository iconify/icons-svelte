<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or4e17b8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="or4e17b8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:new-folder-fill" {...props}></Icon>
