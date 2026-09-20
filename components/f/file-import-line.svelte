<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0uud6bdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0uud6bdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-import-line" {...props}></Icon>
