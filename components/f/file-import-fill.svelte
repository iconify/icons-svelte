<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gux4efbza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gux4efbza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-import-fill" {...props}></Icon>
