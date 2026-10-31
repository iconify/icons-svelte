<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyd5wfbxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yyd5wfbxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:lock-keyhole-gloss" {...props}></Icon>
