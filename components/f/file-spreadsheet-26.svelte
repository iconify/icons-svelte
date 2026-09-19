<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6ojqs_tx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":26};
const content = `<path class="u6ojqs_tx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-spreadsheet-26" {...props}></Icon>
