<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe3u1kbqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qe3u1kbqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-text-solid" {...props}></Icon>
