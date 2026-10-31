<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp0emkwnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tp0emkwnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:badge-x-gloss" {...props}></Icon>
