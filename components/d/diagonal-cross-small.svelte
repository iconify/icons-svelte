<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr6pc4b1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="zr6pc4b1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:diagonal-cross-small" {...props}></Icon>
