<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjd5j7bep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="vjd5j7bep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:agent" {...props}></Icon>
