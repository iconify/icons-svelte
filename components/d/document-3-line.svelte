<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qeaoikbbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qeaoikbbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:document-3-line" {...props}></Icon>
