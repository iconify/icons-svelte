<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tudn0h4za.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tudn0h4za"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bone-fill" {...props}></Icon>
