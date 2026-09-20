<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4sok7wcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4sok7wcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:edge-fill" {...props}></Icon>
