<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jiyu1gbpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jiyu1gbpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ball-remix" {...props}></Icon>
