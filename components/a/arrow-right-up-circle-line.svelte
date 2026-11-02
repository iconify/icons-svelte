<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8xwtbbwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8xwtbbwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-right-up-circle-line" {...props}></Icon>
