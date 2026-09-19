<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwi2rjbdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":352,"height":520};
const content = `<path class="lwi2rjbdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:extinguisher" {...props}></Icon>
