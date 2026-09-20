<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1s88acoe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n1s88acoe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cyborg-remix" {...props}></Icon>
