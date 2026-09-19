<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bepd9obom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bepd9obom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:personal-training" {...props}></Icon>
