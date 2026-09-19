<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0ocn9i_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i0ocn9i_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:ellipsis-vertical-20-solid" {...props}></Icon>
