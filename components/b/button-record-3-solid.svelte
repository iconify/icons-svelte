<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jptnn3ban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="jptnn3ban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:button-record-3-solid" {...props}></Icon>
