<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay2k2nmzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ay2k2nmzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:messages-square-line" {...props}></Icon>
