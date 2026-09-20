<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8rqb8bcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8rqb8bcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:file-exclamation" {...props}></Icon>
