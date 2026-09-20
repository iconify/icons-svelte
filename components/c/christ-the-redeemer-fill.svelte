<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qigz4b1gt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qigz4b1gt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:christ-the-redeemer-fill" {...props}></Icon>
