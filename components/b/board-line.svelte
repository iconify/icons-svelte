<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae7fe4pgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ae7fe4pgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:board-line" {...props}></Icon>
