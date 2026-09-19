<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp_jvhbjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cp_jvhbjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:oval-vertical-filled" {...props}></Icon>
