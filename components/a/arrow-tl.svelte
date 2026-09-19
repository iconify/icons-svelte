<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc056bbuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tc056bbuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:arrow-tl" {...props}></Icon>
