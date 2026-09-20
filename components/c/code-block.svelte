<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyy0evbmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cyy0evbmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:code-block" {...props}></Icon>
