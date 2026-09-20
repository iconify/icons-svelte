<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2k90jzdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u2k90jzdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:battery-low-1-remix" {...props}></Icon>
