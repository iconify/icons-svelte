<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uod0nwcbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uod0nwcbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-left-up-circle-fill" {...props}></Icon>
