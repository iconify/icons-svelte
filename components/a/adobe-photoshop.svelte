<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncwk-2y5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ncwk-2y5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:adobe-photoshop" {...props}></Icon>
