<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cir9vabuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cir9vabuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pencil-circle-filled" {...props}></Icon>
