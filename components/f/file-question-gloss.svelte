<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxex_nckp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxex_nckp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-question-gloss" {...props}></Icon>
