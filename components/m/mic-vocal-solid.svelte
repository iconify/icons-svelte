<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uah1xhj4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uah1xhj4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:mic-vocal-solid" {...props}></Icon>
