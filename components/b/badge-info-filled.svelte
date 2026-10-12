<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5zj4ufve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u5zj4ufve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:badge-info-filled" {...props}></Icon>
