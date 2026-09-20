<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clcbdhbui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="clcbdhbui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flag-1-fill" {...props}></Icon>
