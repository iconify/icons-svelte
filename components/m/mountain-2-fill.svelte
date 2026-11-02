<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-b9ribpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-b9ribpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mountain-2-fill" {...props}></Icon>
