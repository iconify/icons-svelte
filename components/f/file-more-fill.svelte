<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz-z0sb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rz-z0sb-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-more-fill" {...props}></Icon>
