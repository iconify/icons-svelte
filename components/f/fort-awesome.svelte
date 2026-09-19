<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r43xucbqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r43xucbqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:fort-awesome" {...props}></Icon>
