<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4oizhm-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="p4oizhm-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:chevron-down" {...props}></Icon>
