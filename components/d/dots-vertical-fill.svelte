<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqvv5zbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqvv5zbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dots-vertical-fill" {...props}></Icon>
