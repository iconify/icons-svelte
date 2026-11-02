<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x29j5c5kc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x29j5c5kc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-to-right-line" {...props}></Icon>
