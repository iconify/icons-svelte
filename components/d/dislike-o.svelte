<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsdbqmlex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rsdbqmlex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:dislike-o" {...props}></Icon>
