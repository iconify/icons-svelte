<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iug84ickb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="iug84ickb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:circle-remix" {...props}></Icon>
