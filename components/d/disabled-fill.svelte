<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z40mujsla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z40mujsla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:disabled-fill" {...props}></Icon>
