<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k72n2-yze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k72n2-yze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:coin-2-fill" {...props}></Icon>
