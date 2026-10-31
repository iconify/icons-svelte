<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwuh4tb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwuh4tb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-gloss" {...props}></Icon>
