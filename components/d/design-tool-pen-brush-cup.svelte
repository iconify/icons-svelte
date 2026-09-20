<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2luwybss.css';
import '../../css/e/ekdghkqub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2luwybss"/><path class="ekdghkqub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:design-tool-pen-brush-cup" {...props}></Icon>
