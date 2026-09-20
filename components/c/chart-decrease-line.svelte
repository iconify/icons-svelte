<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aihnf6bsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aihnf6bsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-decrease-line" {...props}></Icon>
