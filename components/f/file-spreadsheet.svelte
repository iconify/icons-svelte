<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egdt4zx1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egdt4zx1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-spreadsheet" {...props}></Icon>
