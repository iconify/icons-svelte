<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he5id49mn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="he5id49mn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:computer-pc-desktop-remix" {...props}></Icon>
