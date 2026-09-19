<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb-1labtg.css';
import '../../css/k/kgi65lb8e.css';
import '../../css/l/lmf0ecbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<circle class="wb-1labtg"/><path class="kgi65lb8e"/><circle class="lmf0ecbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:host-solid-badged" {...props}></Icon>
