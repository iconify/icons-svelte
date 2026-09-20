<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twh0pggxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="twh0pggxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:class-lesson-remix" {...props}></Icon>
