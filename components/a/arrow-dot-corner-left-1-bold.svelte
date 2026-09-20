<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve4etabbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ve4etabbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:arrow-dot-corner-left-1-bold" {...props}></Icon>
