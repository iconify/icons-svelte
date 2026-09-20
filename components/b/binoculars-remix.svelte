<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke7fh00we.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ke7fh00we"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:binoculars-remix" {...props}></Icon>
