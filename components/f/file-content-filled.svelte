<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eddf4cbpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eddf4cbpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:file-content-filled" {...props}></Icon>
