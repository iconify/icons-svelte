<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9r2mob8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9r2mob8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hemisphere-2-fill" {...props}></Icon>
