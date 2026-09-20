<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4wpjzb3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="a4wpjzb3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bone-remix" {...props}></Icon>
