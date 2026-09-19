<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx5subbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx5subbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:file-diff" {...props}></Icon>
