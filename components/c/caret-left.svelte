<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk1-7274n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="pk1-7274n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:caret-left" {...props}></Icon>
