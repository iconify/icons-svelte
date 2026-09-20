<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzoxobb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hzoxobb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:line-arrow-split-vertical-up-2-remix" {...props}></Icon>
