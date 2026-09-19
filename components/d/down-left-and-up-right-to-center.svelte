<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7yppybli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="s7yppybli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:down-left-and-up-right-to-center" {...props}></Icon>
