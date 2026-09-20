<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rql910rds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rql910rds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:command-line" {...props}></Icon>
