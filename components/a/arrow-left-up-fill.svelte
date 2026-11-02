<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xghvmkoku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xghvmkoku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-left-up-fill" {...props}></Icon>
