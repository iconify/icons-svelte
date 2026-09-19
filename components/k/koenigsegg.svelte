<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po5guwbfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="po5guwbfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:koenigsegg" {...props}></Icon>
