<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy6m6hb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gy6m6hb8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:lift-out-window-open" {...props}></Icon>
