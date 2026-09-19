<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo2yeabop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jo2yeabop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:exclude" {...props}></Icon>
