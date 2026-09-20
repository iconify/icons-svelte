<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7wvxmbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q7wvxmbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:chess-bishop-remix" {...props}></Icon>
