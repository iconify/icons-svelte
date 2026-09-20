<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1u6f3bkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1u6f3bkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-scan-fill" {...props}></Icon>
