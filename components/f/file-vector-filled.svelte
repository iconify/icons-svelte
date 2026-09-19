<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chcka6bgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="chcka6bgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:file-vector-filled" {...props}></Icon>
