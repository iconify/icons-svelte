<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qus81wbon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qus81wbon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:focus-line" {...props}></Icon>
