<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ary96kbsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":680,"height":694};
const content = `<path class="ary96kbsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:instagram" {...props}></Icon>
