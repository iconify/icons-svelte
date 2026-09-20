<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he98s6lwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="he98s6lwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ladder-remix" {...props}></Icon>
