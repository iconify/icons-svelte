<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwn4e46yu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fwn4e46yu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:arrow-curvy-up-down-2-flat" {...props}></Icon>
