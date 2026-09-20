<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf8ho-irp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zf8ho-irp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:keyboard-outline" {...props}></Icon>
