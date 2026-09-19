<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtbdm7b9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="wtbdm7b9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:ok-sign" {...props}></Icon>
