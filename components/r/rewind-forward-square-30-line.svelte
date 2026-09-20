<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxwx1acpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxwx1acpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-forward-square-30-line" {...props}></Icon>
