<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbn83nkca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbn83nkca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-diff-gloss" {...props}></Icon>
