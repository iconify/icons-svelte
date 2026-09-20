<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6ntohbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6ntohbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fediverse" {...props}></Icon>
