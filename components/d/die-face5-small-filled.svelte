<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0xll1iqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="d0xll1iqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:die-face5-small-filled" {...props}></Icon>
