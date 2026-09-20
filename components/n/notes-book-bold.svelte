<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep6qygbxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ep6qygbxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:notes-book-bold" {...props}></Icon>
