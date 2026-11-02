<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah28l45tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ah28l45tk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:exchange-euro-line" {...props}></Icon>
