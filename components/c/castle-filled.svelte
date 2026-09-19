<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_mxh8b8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_mxh8b8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:castle-filled" {...props}></Icon>
