<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th4v1wbjr.css';
import '../../css/q/qydmu93ss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="th4v1wbjr"/><path class="qydmu93ss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:graduation-cap-filled" {...props}></Icon>
