<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll2fk6ncl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ll2fk6ncl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pencil-3-fill" {...props}></Icon>
