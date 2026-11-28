<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxyl4jfil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxyl4jfil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:folder-arrow-down" {...props}></Icon>
