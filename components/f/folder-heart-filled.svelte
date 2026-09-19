<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbu8cib5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbu8cib5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:folder-heart-filled" {...props}></Icon>
