<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8lfz7jtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8lfz7jtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:classify-3-line" {...props}></Icon>
