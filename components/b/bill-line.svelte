<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co44rmbqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="co44rmbqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bill-line" {...props}></Icon>
