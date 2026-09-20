<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3hyvhbfs.css';
import '../../css/s/swin4bcne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g3hyvhbfs"/><path class="swin4bcne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:notes-book-1" {...props}></Icon>
