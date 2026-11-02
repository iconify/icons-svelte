<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv2vadc9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uv2vadc9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:baby-line" {...props}></Icon>
