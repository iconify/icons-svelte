<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0dzadb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u0dzadb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:recycle-filled" {...props}></Icon>
