<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3u1wjb0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c3u1wjb0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:clipboard-list-filled" {...props}></Icon>
