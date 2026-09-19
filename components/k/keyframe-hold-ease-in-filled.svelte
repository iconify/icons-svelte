<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpn9qcb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dpn9qcb4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:keyframe-hold-ease-in-filled" {...props}></Icon>
