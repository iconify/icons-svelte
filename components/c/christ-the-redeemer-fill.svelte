<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q591nmoit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q591nmoit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:christ-the-redeemer-fill" {...props}></Icon>
