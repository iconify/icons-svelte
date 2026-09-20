<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nseund19v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nseund19v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:file-spreadsheet-sharp-fill" {...props}></Icon>
