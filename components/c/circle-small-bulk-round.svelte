<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcwdquvly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcwdquvly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-small-bulk-round" {...props}></Icon>
