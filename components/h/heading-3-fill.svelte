<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv7jqcbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nv7jqcbug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heading-3-fill" {...props}></Icon>
