<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgbt92b6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jgbt92b6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:album-outline" {...props}></Icon>
