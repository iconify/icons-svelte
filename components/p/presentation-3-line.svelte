<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq31j6bst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eq31j6bst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:presentation-3-line" {...props}></Icon>
