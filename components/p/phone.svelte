<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df1sefjfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="df1sefjfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:phone" {...props}></Icon>
