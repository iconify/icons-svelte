<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9fn-_o-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f9fn-_o-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:fireworks-rocket-remix" {...props}></Icon>
