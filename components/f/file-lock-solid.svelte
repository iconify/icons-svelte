<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ersnx-vyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ersnx-vyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-lock-solid" {...props}></Icon>
