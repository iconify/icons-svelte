<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vap8vfq9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":384};
const content = `<path class="vap8vfq9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:refresh-alt" {...props}></Icon>
