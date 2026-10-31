<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z69_crzqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z69_crzqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:house-plus-gloss" {...props}></Icon>
