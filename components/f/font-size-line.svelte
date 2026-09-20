<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo9crpaok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xo9crpaok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:font-size-line" {...props}></Icon>
