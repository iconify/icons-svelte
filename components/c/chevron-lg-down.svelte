<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe_1fl_8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="oe_1fl_8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:chevron-lg-down" {...props}></Icon>
