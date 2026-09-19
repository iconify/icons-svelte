<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb6w09bir.css';
import '../../css/o/o8fo-jx8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wb6w09bir"/><path class="o8fo-jx8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:eject" {...props}></Icon>
