<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rns7-ac9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rns7-ac9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cyborg-2-solid" {...props}></Icon>
