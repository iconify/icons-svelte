<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urpzf1b4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="urpzf1b4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:notepad-text-solid" {...props}></Icon>
