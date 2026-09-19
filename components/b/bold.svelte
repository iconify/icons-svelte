<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xamjfw8ke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="xamjfw8ke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:bold" {...props}></Icon>
