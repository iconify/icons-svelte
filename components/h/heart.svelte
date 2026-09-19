<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btphczb_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="btphczb_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:heart" {...props}></Icon>
