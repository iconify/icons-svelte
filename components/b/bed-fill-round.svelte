<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0sghcbxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z0sghcbxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bed-fill-round" {...props}></Icon>
