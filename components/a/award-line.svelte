<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxo0tkber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxo0tkber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:award-line" {...props}></Icon>
