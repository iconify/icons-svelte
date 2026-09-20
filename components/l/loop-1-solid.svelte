<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui71xabtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ui71xabtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:loop-1-solid" {...props}></Icon>
