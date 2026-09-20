<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw8ntqb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cw8ntqb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bed-line" {...props}></Icon>
