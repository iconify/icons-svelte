<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4o_4pvin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d4o_4pvin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:dice-2-solid" {...props}></Icon>
