<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p84b_2b8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p84b_2b8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:mail" {...props}></Icon>
