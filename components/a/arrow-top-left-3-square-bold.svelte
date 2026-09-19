<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi03icced.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yi03icced"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-top-left-3-square-bold" {...props}></Icon>
