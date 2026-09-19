<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owkcs8bdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":456,"height":512};
const content = `<path clip-rule="evenodd" class="owkcs8bdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:dosbox-alt" {...props}></Icon>
