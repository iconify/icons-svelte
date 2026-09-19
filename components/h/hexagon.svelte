<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd5_3bctn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="sd5_3bctn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:hexagon" {...props}></Icon>
