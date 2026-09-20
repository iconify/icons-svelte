<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4rmx3eua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n4rmx3eua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bullet-list-remix" {...props}></Icon>
