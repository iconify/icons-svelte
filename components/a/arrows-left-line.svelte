<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo98b5gqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zo98b5gqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrows-left-line" {...props}></Icon>
