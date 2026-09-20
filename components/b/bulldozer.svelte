<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx971zbtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bx971zbtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:bulldozer" {...props}></Icon>
