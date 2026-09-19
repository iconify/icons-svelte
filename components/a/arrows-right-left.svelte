<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4sk3vb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4sk3vb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrows-right-left" {...props}></Icon>
