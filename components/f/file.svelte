<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk9qdyb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bk9qdyb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:file" {...props}></Icon>
