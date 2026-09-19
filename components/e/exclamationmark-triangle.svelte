<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i77-37njs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="i77-37njs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:exclamationmark-triangle" {...props}></Icon>
