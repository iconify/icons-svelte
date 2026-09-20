<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d60h96b6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d60h96b6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:login" {...props}></Icon>
