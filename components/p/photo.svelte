<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhfgwrg9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":666,"height":686};
const content = `<path class="rhfgwrg9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:photo" {...props}></Icon>
