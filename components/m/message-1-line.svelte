<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-e4_4mbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-e4_4mbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-1-line" {...props}></Icon>
