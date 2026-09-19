<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2mfpbxly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2mfpbxly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:fork-spoon-filled" {...props}></Icon>
