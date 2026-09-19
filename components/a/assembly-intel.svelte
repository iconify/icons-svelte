<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv762_3ya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xv762_3ya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:assembly-intel" {...props}></Icon>
