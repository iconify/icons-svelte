<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee582qb8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ee582qb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:picnic-table-in-eaved-gabled-shelter" {...props}></Icon>
