<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aitpvr66y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":328,"height":512};
const content = `<path class="aitpvr66y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:cutlery" {...props}></Icon>
