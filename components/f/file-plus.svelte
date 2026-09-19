<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3u6kqbce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3u6kqbce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:file-plus" {...props}></Icon>
