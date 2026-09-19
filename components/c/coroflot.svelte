<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nybji0bvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":400,"height":488};
const content = `<path class="nybji0bvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:coroflot" {...props}></Icon>
