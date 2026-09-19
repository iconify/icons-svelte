<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxmf65bfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":355,"height":512};
const content = `<path class="xxmf65bfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:easybuild" {...props}></Icon>
