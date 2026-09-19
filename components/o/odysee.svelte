<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c24ihfzcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c24ihfzcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:odysee" {...props}></Icon>
