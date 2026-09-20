<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vleejw2oe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vleejw2oe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:copy-paste-remix" {...props}></Icon>
