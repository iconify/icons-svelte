<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtpzydu5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wtpzydu5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:flip-vertical-square-2-remix" {...props}></Icon>
