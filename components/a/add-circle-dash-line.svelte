<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3vh1xbol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3vh1xbol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:add-circle-dash-line" {...props}></Icon>
