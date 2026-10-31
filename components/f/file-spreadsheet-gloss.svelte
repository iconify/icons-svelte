<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi493krga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xi493krga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-spreadsheet-gloss" {...props}></Icon>
