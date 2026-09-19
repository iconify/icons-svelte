<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btibzlb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":352,"height":488};
const content = `<path class="btibzlb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:official" {...props}></Icon>
