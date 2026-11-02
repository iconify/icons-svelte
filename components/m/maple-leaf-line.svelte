<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt9vprasy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dt9vprasy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:maple-leaf-line" {...props}></Icon>
