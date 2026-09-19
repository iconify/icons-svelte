<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elx1ufbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="elx1ufbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dislike-filled" {...props}></Icon>
