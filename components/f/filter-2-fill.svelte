<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9g9lhbgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f9g9lhbgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:filter-2-fill" {...props}></Icon>
