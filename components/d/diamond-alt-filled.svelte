<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbhyi1bae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbhyi1bae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:diamond-alt-filled" {...props}></Icon>
