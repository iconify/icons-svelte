<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whvybwb6j.css';
import '../../css/d/d0psnynrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="whvybwb6j"/><path class="d0psnynrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:columns-3-cog-filled" {...props}></Icon>
