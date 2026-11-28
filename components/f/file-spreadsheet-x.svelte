<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehr5pjbxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ehr5pjbxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:file-spreadsheet-x" {...props}></Icon>
