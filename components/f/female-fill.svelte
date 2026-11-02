<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxmkffbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxmkffbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:female-fill" {...props}></Icon>
