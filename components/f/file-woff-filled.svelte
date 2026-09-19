<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lowya3gvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="lowya3gvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:file-woff-filled" {...props}></Icon>
