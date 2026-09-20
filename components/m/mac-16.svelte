<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zurdf3b8r.css';
import '../../css/v/vabm_dihy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zurdf3b8r"/><path clip-rule="evenodd" class="vabm_dihy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:mac-16" {...props}></Icon>
