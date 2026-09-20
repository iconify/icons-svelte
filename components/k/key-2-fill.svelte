<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8986pbpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n8986pbpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:key-2-fill" {...props}></Icon>
