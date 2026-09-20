<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxnd1vbda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxnd1vbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:folder-down" {...props}></Icon>
