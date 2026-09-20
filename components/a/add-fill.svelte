<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifw-57x2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ifw-57x2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:add-fill" {...props}></Icon>
