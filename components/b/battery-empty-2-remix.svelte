<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pky2dkb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pky2dkb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:battery-empty-2-remix" {...props}></Icon>
