<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbcdmtbpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hbcdmtbpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:debug-alt" {...props}></Icon>
