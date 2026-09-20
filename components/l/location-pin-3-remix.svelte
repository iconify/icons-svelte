<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx9azvbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xx9azvbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:location-pin-3-remix" {...props}></Icon>
