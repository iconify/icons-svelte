<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_81m919d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c_81m919d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:inbox-lock-remix" {...props}></Icon>
