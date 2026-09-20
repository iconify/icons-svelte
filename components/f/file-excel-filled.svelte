<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r__83nwag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r__83nwag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-excel-filled" {...props}></Icon>
