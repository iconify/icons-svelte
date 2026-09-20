<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwmmrrb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bwmmrrb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frappe-gameplan-light" {...props}></Icon>
