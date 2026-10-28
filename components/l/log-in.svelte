<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-9e6xy9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-9e6xy9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:log-in" {...props}></Icon>
