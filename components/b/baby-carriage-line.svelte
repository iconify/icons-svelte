<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ton41i5am.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ton41i5am"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:baby-carriage-line" {...props}></Icon>
