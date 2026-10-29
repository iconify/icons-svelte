<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks9pbzbgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ks9pbzbgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-minus-solid" {...props}></Icon>
