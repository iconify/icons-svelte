<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-t-g0bba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t-t-g0bba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:inbox-favorite-remix" {...props}></Icon>
