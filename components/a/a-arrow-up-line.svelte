<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0emq8boe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c0emq8boe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:a-arrow-up-line" {...props}></Icon>
