<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osp5j8bui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="osp5j8bui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flag-4-line" {...props}></Icon>
