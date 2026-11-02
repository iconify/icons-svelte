<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7qowt6cs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v7qowt6cs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clock-arrow-down-line" {...props}></Icon>
