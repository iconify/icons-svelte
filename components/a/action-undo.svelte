<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_gptemqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="d_gptemqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:action-undo" {...props}></Icon>
