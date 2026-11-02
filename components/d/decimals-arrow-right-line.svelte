<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aanrabcaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aanrabcaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:decimals-arrow-right-line" {...props}></Icon>
