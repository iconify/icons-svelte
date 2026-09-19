<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jaczkol8s.css';
import '../../css/k/k2yt7cn9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jaczkol8s"/><path class="k2yt7cn9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:content-modified" {...props}></Icon>
