<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyhs67b3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oyhs67b3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flash-line" {...props}></Icon>
