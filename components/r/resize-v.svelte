<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1r1-eb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="s1r1-eb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:resize-v" {...props}></Icon>
