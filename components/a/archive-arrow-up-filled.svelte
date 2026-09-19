<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqkalnmoh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqkalnmoh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:archive-arrow-up-filled" {...props}></Icon>
