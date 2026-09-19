<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry01f3xip.css';
import '../../css/a/a4jsaxbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ry01f3xip"/><path class="a4jsaxbri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:document-solid" {...props}></Icon>
