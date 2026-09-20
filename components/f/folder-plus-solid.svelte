<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4uy-0bwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="t4uy-0bwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:folder-plus-solid" {...props}></Icon>
