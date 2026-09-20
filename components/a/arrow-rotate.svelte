<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly90m4b3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ly90m4b3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-rotate" {...props}></Icon>
