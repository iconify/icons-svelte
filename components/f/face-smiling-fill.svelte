<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdy033b6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="rdy033b6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:face-smiling-fill" {...props}></Icon>
