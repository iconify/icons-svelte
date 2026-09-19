<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jajje8bsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jajje8bsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:noise-filled" {...props}></Icon>
