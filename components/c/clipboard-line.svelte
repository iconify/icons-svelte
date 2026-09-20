<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dee3dzihr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dee3dzihr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clipboard-line" {...props}></Icon>
