<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tokrscowc.css';
import '../../css/l/lmf0ecbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="tokrscowc"/><circle class="lmf0ecbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:media-changer-solid-badged" {...props}></Icon>
