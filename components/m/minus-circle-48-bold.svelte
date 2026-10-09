<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2neunb3u.css';
import '../../css/z/z_g0_6bob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n2neunb3u"/><path class="z_g0_6bob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:minus-circle-48-bold" {...props}></Icon>
