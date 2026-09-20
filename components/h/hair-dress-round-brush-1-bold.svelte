<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sztuft7up.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sztuft7up"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:hair-dress-round-brush-1-bold" {...props}></Icon>
