<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyy7thb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cyy7thb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:plate-wheat" {...props}></Icon>
