<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ju1k4hbss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ju1k4hbss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:honeywell" {...props}></Icon>
