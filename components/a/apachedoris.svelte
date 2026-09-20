<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt4qwgb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vt4qwgb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:apachedoris" {...props}></Icon>
